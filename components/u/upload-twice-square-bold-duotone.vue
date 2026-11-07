<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dm03gzbnp.css';
import '../../css/x/xqdj7wbly.css';
import '../../css/p/p_az3fbck.css';
import '../../css/d/dkneg4bhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dm03gzbnp"/><path class="xqdj7wbly"/><path class="p_az3fbck"/><path class="dkneg4bhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:upload-twice-square-bold-duotone" /></template>
