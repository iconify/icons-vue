<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uyp808bel.css';
import '../../css/a/ar82p3r0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uyp808bel"/><path class="ar82p3r0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:spooty-light" /></template>
