<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eevefobbg.css';
import '../../css/v/vh_x9ccjq.css';
import '../../css/b/bku4shbfc.css';
import '../../css/l/lob6lbb2k.css';
import '../../css/g/gbkh3v4as.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eevefobbg"/><path class="vh_x9ccjq"/><path class="bku4shbfc"/><path class="lob6lbb2k"/><circle class="gbkh3v4as"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:snake" /></template>
