<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ox56n9_ux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ox56n9_ux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:solo" /></template>
