<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kj0bqhbrl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kj0bqhbrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:radio-unchecked" /></template>
