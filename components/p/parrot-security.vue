<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1iq95zjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a1iq95zjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:parrot-security" /></template>
