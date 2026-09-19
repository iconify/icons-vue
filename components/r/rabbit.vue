<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nu-xanbpn.css';
import '../../css/p/pbsi8cc2n.css';
import '../../css/l/l7mgxrb6w.css';
import '../../css/l/lx0r7ilym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="nu-xanbpn"/><path class="pbsi8cc2n"/><path class="l7mgxrb6w"/><path class="lx0r7ilym"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:rabbit" /></template>
