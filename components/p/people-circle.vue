<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-jv-mbrm.css';
import '../../css/t/t5-bpgztj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b-jv-mbrm"/><path class="t5-bpgztj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:people-circle" /></template>
