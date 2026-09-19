<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcwukty_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zcwukty_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:parking-filled" /></template>
