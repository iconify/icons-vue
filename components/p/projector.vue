<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hmqsevbxu.css';
import '../../css/a/a1abklbdz.css';
import '../../css/u/umx108bql.css';
import '../../css/t/tijule18l.css';
import '../../css/e/eap2svbzo.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGY3ppQdLO"><g class="ft5dv1b6b"><path class="hmqsevbxu"/><path class="a1abklbdz"/><path class="umx108bql"/><circle class="tijule18l"/><circle class="eap2svbzo"/></g></mask></defs><path mask="url(#SVGY3ppQdLO)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:projector" /></template>
