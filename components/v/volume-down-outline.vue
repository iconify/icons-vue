<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlo02_iiq.css';
import '../../css/q/qw5e84bjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vlo02_iiq"/><path class="qw5e84bjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:volume-down-outline" /></template>
