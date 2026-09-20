<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbrtl5bbj.css';
import '../../css/q/qvl5apb0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="bbrtl5bbj"/><path class="qvl5apb0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:timer" /></template>
