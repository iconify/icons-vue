<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqr8yp28h.css';
import '../../css/f/f4mdfjbca.css';
import '../../css/x/xm577jbwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fqr8yp28h"/><path class="f4mdfjbca"/><path class="xm577jbwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:webcam-48-bold" /></template>
