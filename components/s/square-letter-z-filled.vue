<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vdaup1bcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vdaup1bcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-letter-z-filled" /></template>
