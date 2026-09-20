<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/ahwjz2bvl.css';
import '../../css/k/kuvr1btsk.css';
import '../../css/s/srl0bo8rs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="ahwjz2bvl"/><path class="kuvr1btsk"/><path class="srl0bo8rs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:youtube-duotone" /></template>
