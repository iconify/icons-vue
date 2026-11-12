<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/df8texbdg.css';
import '../../css/q/q0j4_mbjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="df8texbdg"/><path class="q0j4_mbjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:quickbars-light" /></template>
