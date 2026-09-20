<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hyiq52k8l.css';
import '../../css/m/m1abqtscw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="hyiq52k8l"/><path class="m1abqtscw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:mashroom" /></template>
