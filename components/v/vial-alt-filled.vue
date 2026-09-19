<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvnvbq7cb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wvnvbq7cb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:vial-alt-filled" /></template>
