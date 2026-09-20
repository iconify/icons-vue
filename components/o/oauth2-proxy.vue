<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5l22r1br.css';
import '../../css/j/jsjj4vbkz.css';
import '../../css/b/baxhqnbgk.css';
import '../../css/p/ppetvt7ab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v5l22r1br"/><path class="jsjj4vbkz"/><path class="baxhqnbgk"/><path class="ppetvt7ab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:oauth2-proxy" /></template>
