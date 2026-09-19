<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1xy6nh9u.css';
import '../../css/t/toljrtdpg.css';
import '../../css/r/rpxe9ibnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="n1xy6nh9u"/><circle class="toljrtdpg"/><circle class="rpxe9ibnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:more-vertical-fill" /></template>
