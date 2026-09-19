<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5k2r532v.css';
import '../../css/h/hm-ebxrua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u5k2r532v"/><path class="hm-ebxrua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:quota" /></template>
