<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbu-t6btd.css';
import '../../css/t/t1lgjy0xv.css';
import '../../css/t/tl4cmrb7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kbu-t6btd"/><path class="t1lgjy0xv"/><path class="tl4cmrb7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:x-square-48-bold" /></template>
