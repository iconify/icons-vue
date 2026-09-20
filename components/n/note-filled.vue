<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qw1j5ebjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qw1j5ebjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:note-filled" /></template>
