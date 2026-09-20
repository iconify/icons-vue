<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihrl0fbrp.css';
import '../../css/l/l31-rpb2b.css';
import '../../css/f/f7el6mb9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ihrl0fbrp"/><circle class="l31-rpb2b"/><path class="f7el6mb9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:spinner" /></template>
