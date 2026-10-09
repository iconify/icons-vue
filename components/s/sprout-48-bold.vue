<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/neebw0buz.css';
import '../../css/m/mg2rwedkj.css';
import '../../css/c/cek4p1-qj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="neebw0buz"/><path class="mg2rwedkj"/><path class="cek4p1-qj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sprout-48-bold" /></template>
