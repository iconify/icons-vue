<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwyel9bps.css';
import '../../css/v/vzf2kqbwe.css';
import '../../css/v/vyby-xbyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fwyel9bps"/><path class="vzf2kqbwe"/><path class="vyby-xbyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:radicle-dark" /></template>
