<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trwfcmb-c.css';
import '../../css/j/jzu0kxbzr.css';
import '../../css/m/m98y19b0m.css';
import '../../css/v/vhalmib7e.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/s/s88w27byo.css';
import '../../css/e/e56qzo2wu.css';
import '../../css/g/gno4obbac.css';
import '../../css/x/xig8mrbbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<circle class="trwfcmb-c"/><circle class="jzu0kxbzr"/><circle class="m98y19b0m"/><path class="vhalmib7e"/><g class="jn8qy4bru"><path class="s88w27byo"/><path class="e56qzo2wu"/><path class="gno4obbac"/><path class="xig8mrbbu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:three-finger-operation" /></template>
