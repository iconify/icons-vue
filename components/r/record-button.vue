<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cog56gb0n.css';
import '../../css/v/v9lk8ib_s.css';
import '../../css/h/hf1-0pb9l.css';
import '../../css/w/wtahhnbyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<circle class="cog56gb0n"/><circle class="v9lk8ib_s"/><circle class="hf1-0pb9l"/><circle class="wtahhnbyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:record-button" /></template>
