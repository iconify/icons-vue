<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qb-3h3i8a.css';
import '../../css/t/ttn15vtks.css';
import '../../css/w/wycr1gktp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qb-3h3i8a"/><path clip-rule="evenodd" class="ttn15vtks"/><path class="wycr1gktp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:plus-minus-bold-duotone" /></template>
