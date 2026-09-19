<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/am1rgeb0a.css';
import '../../css/g/gz7h90b8w.css';
import '../../css/u/ugho9_83h.css';
import '../../css/m/mqpwqt44o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="am1rgeb0a"/><path class="gz7h90b8w"/><path class="ugho9_83h"/><circle class="mqpwqt44o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:wifi" /></template>
