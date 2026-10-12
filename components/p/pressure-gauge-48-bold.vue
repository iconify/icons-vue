<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvc4fj9_h.css';
import '../../css/w/wndfuohsw.css';
import '../../css/y/yhk9bj34h.css';
import '../../css/e/ekvf15bga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lvc4fj9_h"/><path class="wndfuohsw"/><path class="yhk9bj34h"/><path class="ekvf15bga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pressure-gauge-48-bold" /></template>
