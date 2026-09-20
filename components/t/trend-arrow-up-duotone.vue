<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3yggvbbt.css';
import '../../css/z/zgmduh90n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g3yggvbbt"/><path class="zgmduh90n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:trend-arrow-up-duotone" /></template>
