<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d4e_esr8j"/><path class="kxwo0lbhm"/><path clip-rule="evenodd" class="pj8n1ebvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:text-bold-duotone" /></template>
<style>
.d4e_esr8j {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8 2h-.066c-.886 0-1.65 0-2.262.082c-.655.088-1.284.287-1.793.797c-.51.51-.709 1.138-.797 1.793C3 5.284 3 6.048 3 6.934V7.95a1 1 0 1 0 2 0V7c0-.971.002-1.599.064-2.061c.059-.434.153-.57.229-.646s.212-.17.646-.229C6.4 4.002 7.029 4 8 4h8c.971 0 1.599.002 2.061.064c.434.059.57.153.646.229s.17.212.229.646C18.998 5.4 19 6.029 19 7v.95a1 1 0 1 0 2 0V6.934c0-.886 0-1.65-.082-2.262c-.088-.655-.287-1.284-.797-1.793c-.51-.51-1.138-.709-1.793-.797C17.716 2 16.952 2 16.066 2z");
}

.kxwo0lbhm {
  fill: currentColor;
  d: path("M13 4h-2v16h2z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.pj8n1ebvk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 21a1 1 0 0 1 1-1h10a1 1 0 1 1 0 2H7a1 1 0 0 1-1-1");
}

</style>
