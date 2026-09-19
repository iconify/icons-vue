<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5bbp6dej.css';
import '../../css/e/e7ba03bxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="n5bbp6dej"/><circle class="e7ba03bxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:tag-stroke-12" /></template>
