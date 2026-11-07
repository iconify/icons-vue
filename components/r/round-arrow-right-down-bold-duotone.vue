<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c77vne7ui.css';
import '../../css/a/aawp35beb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c77vne7ui"/><path class="aawp35beb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:round-arrow-right-down-bold-duotone" /></template>
