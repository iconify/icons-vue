<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xg809gbzw.css';
import '../../css/t/tmzfn5bmd.css';
import '../../css/n/ng9x56bxd.css';
import '../../css/r/rjpe63b-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xg809gbzw"/><path class="tmzfn5bmd"/><path class="ng9x56bxd"/><path class="rjpe63b-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:manltepiececlock" /></template>
