<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6z4n_brj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i6z4n_brj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:pull-request-line" /></template>
