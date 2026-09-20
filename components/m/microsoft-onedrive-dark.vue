<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzxu6cbem.css';
import '../../css/l/l5bgdtbpm.css';
import '../../css/t/t9nocfb7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gzxu6cbem"/><path class="l5bgdtbpm"/><path class="t9nocfb7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-onedrive-dark" /></template>
