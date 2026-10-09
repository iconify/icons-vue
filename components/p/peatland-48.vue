<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/za30h5bbb.css';
import '../../css/n/no53kdbqh.css';
import '../../css/l/lr5jr9ons.css';
import '../../css/x/xopzt8bhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="za30h5bbb"/><path class="no53kdbqh"/><path class="lr5jr9ons"/><path class="xopzt8bhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:peatland-48" /></template>
