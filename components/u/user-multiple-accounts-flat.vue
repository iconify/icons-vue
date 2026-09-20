<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/l/lo1dnac6c.css';
import '../../css/z/zp6ey7xyk.css';
import '../../css/s/sv6qal5dy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="lo1dnac6c"/><path class="zp6ey7xyk"/><path class="sv6qal5dy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump-color:user-multiple-accounts-flat" /></template>
