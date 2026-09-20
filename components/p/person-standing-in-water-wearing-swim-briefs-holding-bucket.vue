<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uj9vsub_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="uj9vsub_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-standing-in-water-wearing-swim-briefs-holding-bucket" /></template>
