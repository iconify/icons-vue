<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aw82aw3si.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="aw82aw3si"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:munin-light" /></template>
