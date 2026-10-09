<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8zhq3bqa.css';
import '../../css/k/k3148ab8q.css';
import '../../css/x/xmpbrx25v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e8zhq3bqa"/><path class="k3148ab8q"/><path class="xmpbrx25v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-kit-48" /></template>
