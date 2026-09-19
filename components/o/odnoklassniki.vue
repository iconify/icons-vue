<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jotw69_ei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jotw69_ei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:odnoklassniki" /></template>
