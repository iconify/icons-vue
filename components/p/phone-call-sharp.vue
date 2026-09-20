<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pansjw__x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pansjw__x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:phone-call-sharp" /></template>
