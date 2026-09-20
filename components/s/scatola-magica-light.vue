<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5py7xbsd.css';
import '../../css/w/wd2bk8qje.css';
import '../../css/e/ey4nidbgq.css';
import '../../css/x/x3sba3w-q.css';
import '../../css/p/pquylo05r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u5py7xbsd"/><path class="wd2bk8qje"/><path class="ey4nidbgq"/><path class="x3sba3w-q"/><path class="pquylo05r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:scatola-magica-light" /></template>
