<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ii1sy95ok.css';
import '../../css/n/npymy_hkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ii1sy95ok"/><path class="npymy_hkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:square-academic-cap-bold-duotone" /></template>
