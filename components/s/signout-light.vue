<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5g1yj-up.css';
import '../../css/v/vv-w0sjvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t5g1yj-up"/><path class="vv-w0sjvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:signout-light" /></template>
