<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_vn9-b7l.css';
import '../../css/k/kj4xs5bkc.css';
import '../../css/g/gxky-sbxf.css';
import '../../css/o/o3qyi4q4j.css';
import '../../css/n/nq5_p_bzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="g_vn9-b7l"/><path class="kj4xs5bkc"/><path class="gxky-sbxf"/><path class="o3qyi4q4j"/><path class="nq5_p_bzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:thermostat-alert-20" /></template>
