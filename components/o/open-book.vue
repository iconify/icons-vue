<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="zt5it0bhf"/><path class="clniikb0p"/><path class="abiwg8b7f"/><path class="ywbnu0udt"/><path class="u0a_0gbwi"/><path class="w6bcyrbaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:open-book" /></template>
<style>
.abiwg8b7f {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M18 26a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2z");
}

.clniikb0p {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M20 27a2 2 0 0 1-4 0V9a2 2 0 0 1 4 0z");
}

.u0a_0gbwi {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M34 26a2 2 0 0 1-2 2H20a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2z");
}

.w6bcyrbaj {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M18 26c.999-1.998 3.657-2 4-2c2 0 5 2 8 2c1 0 2-.896 2-2V8c0-1.104-1-2-2-2c-3.256 0-6-2-8-2c-3 0-4 1.896-4 3z");
}

.ywbnu0udt {
  fill: var(--svg-color--e1e8ed, #e1e8ed);
  d: path("M18 26c-.999-1.998-3.657-2-4-2c-2 0-5 2-8 2c-1 0-2-.896-2-2V8c0-1.104 1-2 2-2c3.255 0 6-2 8-2c3 0 4 1.896 4 3z");
}

.zt5it0bhf {
  fill: var(--svg-color--269, #269);
  d: path("M32 7H4a4 4 0 0 0-4 4v15a4 4 0 0 0 4 4h11.416c.52.596 1.477 1 2.584 1s2.065-.404 2.584-1H32a4 4 0 0 0 4-4V11a4 4 0 0 0-4-4");
}

</style>
