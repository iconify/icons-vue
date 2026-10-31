<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nh_u97f-x.css';
import '../../css/f/f5rb8abwp.css';
import '../../css/z/zy0c3b-sv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="nh_u97f-x"/><path class="f5rb8abwp"/><path class="zy0c3b-sv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:saint-vincent-and-grenadines" /></template>
