<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/y/y3wwogb_e.css';
import '../../css/o/omos15brj.css';
import '../../css/n/np6wssw9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<g class="bi12bsetm"><path class="y3wwogb_e"/><path class="omos15brj"/><path class="np6wssw9i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:socketio-wordmark" /></template>
