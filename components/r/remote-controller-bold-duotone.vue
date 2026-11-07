<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/be24kjn_m.css';
import '../../css/m/mybsyle5g.css';
import '../../css/e/e60e9tbne.css';
import '../../css/g/gn332x-gl.css';
import '../../css/u/uby1kqbbu.css';
import '../../css/q/qwv8yacfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="be24kjn_m"/><path clip-rule="evenodd" class="mybsyle5g"/><path class="e60e9tbne"/><path class="gn332x-gl"/><path class="uby1kqbbu"/><path class="qwv8yacfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:remote-controller-bold-duotone" /></template>
