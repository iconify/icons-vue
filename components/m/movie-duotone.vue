<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8wdtyblq.css';
import '../../css/m/mn3wcdgwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e8wdtyblq"/><path class="mn3wcdgwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:movie-duotone" /></template>
