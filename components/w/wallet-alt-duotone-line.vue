<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/l10su6f3a.css';
import '../../css/s/s6jk32b5k.css';
import '../../css/c/c25nhu92o.css';
import '../../css/b/bpiis4b2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="l10su6f3a"/><path class="s6jk32b5k"/><path class="c25nhu92o"/><path class="bpiis4b2u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:wallet-alt-duotone-line" /></template>
