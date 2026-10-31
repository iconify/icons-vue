<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/k/k3rplwb3c.css';
import '../../css/r/rw4tztb5c.css';
import '../../css/g/gbm7u0p8v.css';
import '../../css/i/i36_dacbt.css';
import '../../css/f/ffoonvqme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="k3rplwb3c wm-shadow"/><path class="rw4tztb5c wm-shadow"/><path class="gbm7u0p8v"/><path class="i36_dacbt"/><path class="ffoonvqme"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:pencil-ruler" /></template>
