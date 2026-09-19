<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqwu_c0kl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rqwu_c0kl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:png-file-filled" /></template>
