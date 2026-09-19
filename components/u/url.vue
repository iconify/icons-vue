<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4n_m3bat.css';
import '../../css/w/wa7qyq31a.css';
import '../../css/q/qasg3hbws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":13,"height":16};
const content = `<circle class="a4n_m3bat"/><circle class="wa7qyq31a"/><path class="qasg3hbws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:url" /></template>
