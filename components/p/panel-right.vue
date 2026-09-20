<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b69zoybux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="b69zoybux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:panel-right" /></template>
