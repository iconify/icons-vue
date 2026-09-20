<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qw1iverzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qw1iverzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:shock-absorber" /></template>
