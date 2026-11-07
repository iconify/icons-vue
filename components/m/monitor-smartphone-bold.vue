<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pt9l_-hve.css';
import '../../css/g/gazl242lv.css';
import '../../css/q/qw8mp2b-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pt9l_-hve"/><path class="gazl242lv"/><path clip-rule="evenodd" class="qw8mp2b-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:monitor-smartphone-bold" /></template>
