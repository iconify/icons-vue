<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnek95zaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bnek95zaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:sign-out-alt-line" /></template>
