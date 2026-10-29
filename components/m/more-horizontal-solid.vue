<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jj18p3v6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jj18p3v6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:more-horizontal-solid" /></template>
