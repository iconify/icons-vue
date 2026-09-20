<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="jt2qgtbhl"/><path class="mpmdgtbqk"/><path class="c_l0t45ez"/><path class="e6_8at6sw"/><path class="p42f6jb6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:takeout-box" /></template>
<style>
.c_l0t45ez {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M34.901.567A1 1 0 0 0 34 0H16a1 1 0 0 0-.781.375L9.439 7H12l4.48-5h15.438l-6.7 8.375a1 1 0 0 0 1.563 1.25l8-10c.24-.3.286-.712.12-1.058");
}

.e6_8at6sw {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("M30.495 32h-14l2.159-3h10zm-3.073-4h-7.429l.768-1h6zm1.392-2h-10l2.159-3h6zm-1.787-4h-6l1.053-1h4zm.106-2h-6l2.159-3h2zm-1.787-4h-2l1.159-3z");
}

.jt2qgtbhl {
  fill: var(--svg-color--e1e8ed, #e1e8ed);
  d: path("M34 7H2l3 29h26z");
}

.mpmdgtbqk {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M14 7H2l3 29h10z");
}

.p42f6jb6z {
  fill: var(--svg-color--be1931, #be1931);
  d: path("M14.008 32H5.169l.944-3h6.314zm-2.499-4h-4.69l.345-1h3.788zm.599-2H5.795l.944-3h3.789zm-1.686-4H6.633l.526-1h2.525zm-.213-2H6.421l.945-3h1.262zm-1.687-4H7.26l.313-3z");
}

</style>
