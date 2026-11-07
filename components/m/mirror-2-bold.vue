<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l33hdlfbw.css';
import '../../css/x/x_lq2pb5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l33hdlfbw"/><path class="x_lq2pb5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:mirror-2-bold" /></template>
