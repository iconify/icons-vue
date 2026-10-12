<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldfradshm.css';
import '../../css/i/itrl4jbne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ldfradshm"/><path class="itrl4jbne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:midi-port-filled" /></template>
