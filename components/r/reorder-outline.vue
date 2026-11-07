<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c80kiybsf.css';
import '../../css/i/ib6qaybse.css';
import '../../css/e/efa1bkb1o.css';
import '../../css/d/dntz9tmey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c80kiybsf"/><path class="ib6qaybse"/><path class="efa1bkb1o"/><path class="dntz9tmey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:reorder-outline" /></template>
