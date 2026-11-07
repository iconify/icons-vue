<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9u-03p8n.css';
import '../../css/k/keuudrbox.css';
import '../../css/j/js631gbug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q9u-03p8n"/><path class="keuudrbox"/><path class="js631gbug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panel-left-open-bold-duotone" /></template>
