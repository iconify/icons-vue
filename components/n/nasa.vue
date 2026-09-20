<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adzm42zuk.css';
import '../../css/s/s8ope8btg.css';
import '../../css/p/pp0f03bez.css';
import '../../css/q/q8h4qbb9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="adzm42zuk"/><path class="s8ope8btg"/><path class="pp0f03bez"/><path class="q8h4qbb9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nasa" /></template>
