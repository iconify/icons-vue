<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ne2sisi1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ne2sisi1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:reset" /></template>
