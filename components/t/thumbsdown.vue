<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fj4k0mbbu.css';
import '../../css/m/mpad8yq0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":470};
const content = `<path class="fj4k0mbbu"/><path class="mpad8yq0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:thumbsdown" /></template>
