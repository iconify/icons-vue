<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpm5gpbgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tpm5gpbgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:toothbrush-alt-filled" /></template>
