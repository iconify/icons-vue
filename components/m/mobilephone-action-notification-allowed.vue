<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/n/nrhq9wbem.css';
import '../../css/g/goloxm9_l.css';
import '../../css/w/w_b4t0bzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="nrhq9wbem"/><path class="goloxm9_l"/><path class="w_b4t0bzz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:mobilephone-action-notification-allowed" /></template>
