<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gb7_855gm.css';
import '../../css/o/oieq8dp3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gb7_855gm"/><path class="oieq8dp3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:phone-paused-duotone" /></template>
