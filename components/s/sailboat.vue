<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rb9sotsen.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rb9sotsen"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:sailboat" /></template>
