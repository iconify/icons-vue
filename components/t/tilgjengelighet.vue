<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aeyw3hn-y.css';
import '../../css/f/fdorp31hk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aeyw3hn-y"/><path class="fdorp31hk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:tilgjengelighet" /></template>
