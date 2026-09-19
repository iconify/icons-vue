<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qw-5i4bdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qw-5i4bdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:property-new" /></template>
