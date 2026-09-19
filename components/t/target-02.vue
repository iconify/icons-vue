<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/h4pc6jngq.css';
import '../../css/w/wkm6c6j9i.css';
import '../../css/a/a5k_nab9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="h4pc6jngq"/><path class="wkm6c6j9i"/><path class="a5k_nab9u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:target-02" /></template>
