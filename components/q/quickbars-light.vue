<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/df8texbdg.css';
import '../../css/e/eg-j-vy9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="df8texbdg"/><path class="eg-j-vy9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:quickbars-light" /></template>
