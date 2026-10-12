<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qw8ygub3e.css';
import '../../css/k/k7-izcbee.css';
import '../../css/e/e_r9uibzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qw8ygub3e"/><path class="k7-izcbee"/><path class="e_r9uibzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:save-check-filled" /></template>
