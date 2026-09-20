<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ay0p6rq1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ay0p6rq1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:photon" /></template>
