<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6xc7b-8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p6xc7b-8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:phone-routing-filled" /></template>
