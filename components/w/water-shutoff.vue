<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y40u92bbl.css';
import '../../css/e/ejog3cncc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="y40u92bbl"/><path class="ejog3cncc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:water-shutoff" /></template>
