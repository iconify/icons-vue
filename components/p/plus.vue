<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vm7pf2ban.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="vm7pf2ban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:plus" /></template>
