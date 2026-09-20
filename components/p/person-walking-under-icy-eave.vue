<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apl3tib4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="apl3tib4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-walking-under-icy-eave" /></template>
