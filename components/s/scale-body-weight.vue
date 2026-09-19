<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hydaclj-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hydaclj-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:scale-body-weight" /></template>
