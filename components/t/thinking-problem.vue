<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwvp95byt.css';
import '../../css/b/bi-0wkbso.css';
import '../../css/c/cyxc_lbvc.css';
import '../../css/i/ixr36dbus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="wwvp95byt"><path class="bi-0wkbso"/><path class="cyxc_lbvc"/><path class="ixr36dbus"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:thinking-problem" /></template>
