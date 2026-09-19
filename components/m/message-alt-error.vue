<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_30szf3s.css';
import '../../css/m/myoip7bjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_30szf3s"/><path class="myoip7bjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:message-alt-error" /></template>
