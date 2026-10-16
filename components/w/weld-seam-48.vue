<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpwsvx0jv.css';
import '../../css/n/n-kljywsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kpwsvx0jv"/><path class="n-kljywsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:weld-seam-48" /></template>
