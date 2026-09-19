<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sunnwjbfh.css';
import '../../css/k/k6q-kjzhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sunnwjbfh"/><path class="k6q-kjzhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:system-warning" /></template>
