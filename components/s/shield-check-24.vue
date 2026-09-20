<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jnbdw3x9y.css';
import '../../css/u/uxsu2sb9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jnbdw3x9y"/><path class="uxsu2sb9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:shield-check-24" /></template>
