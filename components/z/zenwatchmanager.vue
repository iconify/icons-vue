<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="a1civftgv"/><path class="yjuusyban"/><path class="wqfd1sbym"/><path class="oy55x1bkn"/><path class="nu8z3r6wp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:zenwatchmanager" /></template>
<style>
.a1civftgv {
  d: path("M38.99 7.765H9.01c-1.003 0-1.817.785-1.817 1.752v28.915c0 .968.814 1.753 1.817 1.753h29.98c1.003 0 1.817-.785 1.817-1.753h0V9.517c0-.967-.814-1.752-1.817-1.752");
}

.nu8z3r6wp {
  d: path("M28 24.238a4 4 0 0 1-4 4h0a4 4 0 0 1-4-4h0a4 4 0 0 1 4-4h0a4 4 0 0 1 4 4");
}

.oy55x1bkn {
  d: path("M25.5 24.238a1.5 1.5 0 1 1-1.5-1.5h0a1.5 1.5 0 0 1 1.5 1.5");
}

.wqfd1sbym {
  d: path("m22.3 15.27l2.833-.048l.425 2.596l1.18.708l2.454-1.604l2.03 1.84l-1.464 2.172l.52 1.51l3.162.472l.047 2.454l-2.785.284l-.99 1.557l1.415 2.171l-1.84 1.888l-2.03-1.416l-1.37.614l-.471 2.785l-2.926-.095l-.52-2.784l-1.463-.708l-1.982 1.604l-1.935-1.982l1.368-1.888l-.896-1.605l-2.55-.189l.095-2.831l2.455-.095l.944-1.7l-1.416-2.076l1.935-1.935l1.652 1.51l1.699-.66z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yjuusyban {
  d: path("M35.668 11.155H12.332c-.78 0-1.414.626-1.414 1.397h0v23.037c0 .771.633 1.396 1.414 1.396h23.336c.78 0 1.414-.625 1.414-1.396V12.552c0-.771-.633-1.397-1.414-1.397m-23.531-3.39V5.5h23.346v2.265M12.35 40.185V42.5h23.038v-2.315");
}

</style>
