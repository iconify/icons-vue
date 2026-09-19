<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wi5iwqbby.css';
import '../../css/q/qqdx66bkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="wi5iwqbby"/><path class="qqdx66bkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:vagrant-wordmark" /></template>
