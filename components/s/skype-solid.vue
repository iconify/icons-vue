<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvwlt_bnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="tvwlt_bnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:skype-solid" /></template>
