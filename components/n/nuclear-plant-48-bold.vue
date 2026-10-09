<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yo3rjpgxd.css';
import '../../css/d/dujsdbckk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yo3rjpgxd"/><path class="dujsdbckk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:nuclear-plant-48-bold" /></template>
