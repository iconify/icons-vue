<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jakgx-bvd.css';
import '../../css/j/jzt-i4bdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jakgx-bvd"/><path class="jzt-i4bdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:phonon" /></template>
