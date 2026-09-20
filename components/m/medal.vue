<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qe6d94qfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qe6d94qfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:medal" /></template>
