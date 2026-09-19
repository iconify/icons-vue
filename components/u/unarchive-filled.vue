<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lixw4acud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lixw4acud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:unarchive-filled" /></template>
