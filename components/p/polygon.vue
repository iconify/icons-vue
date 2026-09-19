<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/auooq3bgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="auooq3bgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:polygon" /></template>
