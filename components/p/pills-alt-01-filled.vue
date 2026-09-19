<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zywujyb1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zywujyb1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:pills-alt-01-filled" /></template>
