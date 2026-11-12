<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hscy5fdck.css';
import '../../css/k/kdlzsghls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hscy5fdck"/><path class="kdlzsghls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:oauth2-proxy-light" /></template>
