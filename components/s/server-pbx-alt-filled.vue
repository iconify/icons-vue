<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbos7x4cn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nbos7x4cn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:server-pbx-alt-filled" /></template>
