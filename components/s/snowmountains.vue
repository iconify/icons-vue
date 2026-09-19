<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mltz1-3_c.css';
import '../../css/h/hzwaagb3g.css';
import '../../css/t/tgddkdmlp.css';
import '../../css/k/ky6vsbbsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mltz1-3_c"/><path class="hzwaagb3g"/><path class="tgddkdmlp"/><path class="ky6vsbbsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:snowmountains" /></template>
