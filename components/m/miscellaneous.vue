<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l88as7bei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l88as7bei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:miscellaneous" /></template>
