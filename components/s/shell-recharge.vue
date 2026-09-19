<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aj1lpsbel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aj1lpsbel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:shell-recharge" /></template>
