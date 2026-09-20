<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mechmg1pl.css';
import '../../css/f/fvdb48b-r.css';
import '../../css/g/gy17i4r8b.css';
import '../../css/f/fxhttsn0u.css';
import '../../css/u/ucdiad9nq.css';
import '../../css/f/fqlijmbsc.css';
import '../../css/u/uwullu9jn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<rect class="mechmg1pl"/><path class="fvdb48b-r"/><path class="gy17i4r8b"/><path class="fxhttsn0u"/><circle class="ucdiad9nq"/><path class="fqlijmbsc"/><path class="uwullu9jn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:mobile-message" /></template>
