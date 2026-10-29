<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjwqr1b2g.css';
import '../../css/h/hctk37wzh.css';
import '../../css/l/lid4jmbmv.css';
import '../../css/m/mp6row0-y.css';
import '../../css/u/ugu3xyw4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bjwqr1b2g wm-k"/><path class="hctk37wzh wm-k"/><path class="lid4jmbmv wm-a"/><path class="mp6row0-y wm-s"/><path class="ugu3xyw4k wm-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:sunrise" /></template>
