<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqaaen3kj.css';
import '../../css/a/ac-8vg33b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nqaaen3kj"/><path class="ac-8vg33b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:perfice" /></template>
