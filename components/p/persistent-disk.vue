<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nm_i66_ym.css';
import '../../css/o/ojwmqkoww.css';
import '../../css/x/xrhdcypyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nm_i66_ym"/><path class="ojwmqkoww"/><path class="xrhdcypyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:persistent-disk" /></template>
