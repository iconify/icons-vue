<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8dyr0iia.css';
import '../../css/m/m1hyp0bms.css';
import '../../css/c/c02oijjub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m8dyr0iia"/><path class="m1hyp0bms"/><path class="c02oijjub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:repeat-20" /></template>
