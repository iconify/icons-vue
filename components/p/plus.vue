<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ch550_68c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ch550_68c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:plus" /></template>
