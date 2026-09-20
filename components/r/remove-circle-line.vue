<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-8enguzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-8enguzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:remove-circle-line" /></template>
